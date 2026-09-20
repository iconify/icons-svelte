<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dky4z0bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dky4z0bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-to-right" {...props}></Icon>
