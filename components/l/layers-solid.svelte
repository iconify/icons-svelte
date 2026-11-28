<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5b2u0bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5b2u0bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-solid" {...props}></Icon>
