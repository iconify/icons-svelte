<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-e1deksh.css';
import '../../css/d/dzrwv9dgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-e1deksh"/><path class="dzrwv9dgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:copy" {...props}></Icon>
