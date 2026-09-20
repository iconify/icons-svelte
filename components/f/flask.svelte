<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffb0y8qbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffb0y8qbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:flask" {...props}></Icon>
