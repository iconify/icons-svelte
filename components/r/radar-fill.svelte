<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtc2tdbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtc2tdbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:radar-fill" {...props}></Icon>
