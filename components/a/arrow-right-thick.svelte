<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj02-s9_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj02-s9_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-right-thick" {...props}></Icon>
