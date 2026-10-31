<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyf3pjg2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyf3pjg2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-lightning-fill-round" {...props}></Icon>
