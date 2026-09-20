<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1gbxh8hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1gbxh8hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aiqfome" {...props}></Icon>
