<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht17a1bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht17a1bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:move-up-left" {...props}></Icon>
