<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq9e_tbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq9e_tbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:angular" {...props}></Icon>
