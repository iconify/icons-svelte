<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihgfy3ggy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihgfy3ggy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:android" {...props}></Icon>
