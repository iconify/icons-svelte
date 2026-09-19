<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6xmx6owm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6xmx6owm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:box-list" {...props}></Icon>
