<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucn4fhbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucn4fhbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:insert-row-bottom" {...props}></Icon>
