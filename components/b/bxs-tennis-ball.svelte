<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v439n2bfl.css';
import '../../css/d/dcra57g9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v439n2bfl"/><path class="dcra57g9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-tennis-ball" {...props}></Icon>
