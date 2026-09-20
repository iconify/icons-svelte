<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czh9m92jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czh9m92jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pizza-solid" {...props}></Icon>
