<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx3zk3vyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx3zk3vyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-left-outline" {...props}></Icon>
