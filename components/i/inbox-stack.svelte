<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ausqiqdld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ausqiqdld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:inbox-stack" {...props}></Icon>
