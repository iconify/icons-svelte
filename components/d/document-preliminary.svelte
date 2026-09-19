<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkb1tcc5d.css';
import '../../css/k/k2n9vabow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pkb1tcc5d"/><path class="k2n9vabow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-preliminary" {...props}></Icon>
