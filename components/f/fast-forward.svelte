<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek0m9mbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek0m9mbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fast-forward" {...props}></Icon>
