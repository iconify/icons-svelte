<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr5v-mbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr5v-mbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-left-filled" {...props}></Icon>
