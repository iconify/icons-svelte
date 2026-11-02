<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haimgbp7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haimgbp7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-1-fill" {...props}></Icon>
