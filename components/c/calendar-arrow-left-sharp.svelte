<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af0flxbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af0flxbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-left-sharp" {...props}></Icon>
