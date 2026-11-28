<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f00lv-bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f00lv-bek primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:refresh-duotone" {...props}></Icon>
