<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8s_7ub3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8s_7ub3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:edge" {...props}></Icon>
