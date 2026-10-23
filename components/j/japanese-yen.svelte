<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgcxa8y2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgcxa8y2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:japanese-yen" {...props}></Icon>
