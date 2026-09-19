<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipjz1gbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipjz1gbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-alt-filled" {...props}></Icon>
