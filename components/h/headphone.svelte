<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlsnkg_mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlsnkg_mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:headphone" {...props}></Icon>
