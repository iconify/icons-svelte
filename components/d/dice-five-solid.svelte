<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu1llj41y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu1llj41y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-five-solid" {...props}></Icon>
