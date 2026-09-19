<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a33d7c0oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a33d7c0oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:fingerprint-outline" {...props}></Icon>
