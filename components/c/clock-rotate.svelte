<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-wnu-1im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-wnu-1im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:clock-rotate" {...props}></Icon>
