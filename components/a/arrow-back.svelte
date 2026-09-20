<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njxp6oxrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njxp6oxrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-back" {...props}></Icon>
