<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww0ts7b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww0ts7b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:patreon" {...props}></Icon>
