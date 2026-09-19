<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk3anbc7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vk3anbc7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:backward" {...props}></Icon>
