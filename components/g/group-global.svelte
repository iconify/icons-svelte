<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mckkhbbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mckkhbbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:group-global" {...props}></Icon>
