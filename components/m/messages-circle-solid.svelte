<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlp59pc0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlp59pc0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:messages-circle-solid" {...props}></Icon>
