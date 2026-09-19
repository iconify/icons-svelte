<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv5n3jbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv5n3jbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:minimize-2" {...props}></Icon>
