<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1ytjzj6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1ytjzj6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:android" {...props}></Icon>
