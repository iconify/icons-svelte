<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcb3j8zio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wcb3j8zio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:anus-24px" {...props}></Icon>
