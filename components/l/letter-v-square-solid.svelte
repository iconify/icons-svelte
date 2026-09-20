<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-9ht2b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-9ht2b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-v-square-solid" {...props}></Icon>
