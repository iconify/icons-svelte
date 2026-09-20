<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_o2gabit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_o2gabit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:blitz" {...props}></Icon>
