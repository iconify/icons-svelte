<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0hqf1bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0hqf1bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:music-note" {...props}></Icon>
