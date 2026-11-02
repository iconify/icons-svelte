<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dad9wjbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dad9wjbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-3-fill" {...props}></Icon>
