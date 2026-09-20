<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqo72weep.css';
import '../../css/h/h339_5zrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pqo72weep"/><path class="h339_5zrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rc" {...props}></Icon>
