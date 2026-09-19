<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efjpyloka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efjpyloka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pc-mouse" {...props}></Icon>
