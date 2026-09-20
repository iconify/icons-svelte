<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru1o54b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru1o54b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrows-up-from-line-solid" {...props}></Icon>
