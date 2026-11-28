<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtgod5c3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtgod5c3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:repeat-solid" {...props}></Icon>
