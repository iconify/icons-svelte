<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zurlrabfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zurlrabfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:number-2-square-solid" {...props}></Icon>
