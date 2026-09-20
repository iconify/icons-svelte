<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzkzy7e_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzkzy7e_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dice-1-solid" {...props}></Icon>
