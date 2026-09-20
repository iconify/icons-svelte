<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mev0ftb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mev0ftb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bucket-circle-filled" {...props}></Icon>
