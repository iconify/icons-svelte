<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk-w9rb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk-w9rb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:device-mobile" {...props}></Icon>
