<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku84tqx2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ku84tqx2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:monogram" {...props}></Icon>
