<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi5tv6bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi5tv6bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:newspaper-plus" {...props}></Icon>
