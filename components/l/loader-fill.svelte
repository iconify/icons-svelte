<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf0ymuc-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf0ymuc-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:loader-fill" {...props}></Icon>
