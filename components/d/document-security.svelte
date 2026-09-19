<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-v_r1sov.css';
import '../../css/k/k2n9vabow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b-v_r1sov"/><path class="k2n9vabow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-security" {...props}></Icon>
