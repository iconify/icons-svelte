<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp-kft8it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp-kft8it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:building" {...props}></Icon>
