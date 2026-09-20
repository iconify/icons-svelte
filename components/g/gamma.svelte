<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4spl7m6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4spl7m6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamma" {...props}></Icon>
