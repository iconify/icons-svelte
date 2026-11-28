<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-rh7-bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-rh7-bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-alert" {...props}></Icon>
