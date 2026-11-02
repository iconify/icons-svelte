<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3idg1mlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3idg1mlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-fill" {...props}></Icon>
