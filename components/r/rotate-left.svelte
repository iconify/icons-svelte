<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zenzxyzmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zenzxyzmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rotate-left" {...props}></Icon>
