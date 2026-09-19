<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm5zgub6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1536};
const content = `<path class="pm5zgub6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:credit-card" {...props}></Icon>
