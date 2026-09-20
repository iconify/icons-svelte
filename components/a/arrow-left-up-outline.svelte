<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yipfkb_er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yipfkb_er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-up-outline" {...props}></Icon>
