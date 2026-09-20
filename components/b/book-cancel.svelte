<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtqdbmbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtqdbmbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-cancel" {...props}></Icon>
