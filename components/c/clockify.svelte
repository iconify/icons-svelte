<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkumzcb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkumzcb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:clockify" {...props}></Icon>
