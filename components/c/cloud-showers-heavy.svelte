<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3f0bobfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3f0bobfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-showers-heavy" {...props}></Icon>
