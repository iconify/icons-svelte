<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y20o_wd6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y20o_wd6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:headphones-off-solid" {...props}></Icon>
