<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkzxq9dxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkzxq9dxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:archive" {...props}></Icon>
