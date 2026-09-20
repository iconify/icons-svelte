<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxfhco1bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxfhco1bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-thin-circle-outline" {...props}></Icon>
