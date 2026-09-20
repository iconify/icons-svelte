<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzegd0b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzegd0b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-waves-solid" {...props}></Icon>
