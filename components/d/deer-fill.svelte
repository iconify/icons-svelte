<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5fs7yqvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5fs7yqvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:deer-fill" {...props}></Icon>
