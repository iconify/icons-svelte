<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idj3iibuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idj3iibuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-waves" {...props}></Icon>
