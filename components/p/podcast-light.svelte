<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc78iibhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yc78iibhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:podcast-light" {...props}></Icon>
