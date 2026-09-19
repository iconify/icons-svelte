<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2blh85iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2blh85iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-down-up" {...props}></Icon>
