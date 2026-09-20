<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdoh0m-2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdoh0m-2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:color-tuning" {...props}></Icon>
