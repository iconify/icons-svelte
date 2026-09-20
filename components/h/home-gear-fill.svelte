<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg_5v1b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg_5v1b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-gear-fill" {...props}></Icon>
