<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4fs-vakd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4fs-vakd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bring-front" {...props}></Icon>
