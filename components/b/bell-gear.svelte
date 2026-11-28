<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olo-xgmyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olo-xgmyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bell-gear" {...props}></Icon>
