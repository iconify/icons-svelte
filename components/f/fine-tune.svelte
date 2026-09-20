<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnxvq404g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnxvq404g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fine-tune" {...props}></Icon>
