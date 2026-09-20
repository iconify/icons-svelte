<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lihl_43df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lihl_43df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-industrial" {...props}></Icon>
