<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwxp3gbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwxp3gbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-up-left-bold" {...props}></Icon>
