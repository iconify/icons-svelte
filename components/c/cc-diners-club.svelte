<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngd0dh-ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ngd0dh-ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-diners-club" {...props}></Icon>
