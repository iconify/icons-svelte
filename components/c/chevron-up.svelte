<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4cmheptx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v4cmheptx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:chevron-up" {...props}></Icon>
