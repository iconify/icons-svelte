<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqwm87bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yqwm87bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:image" {...props}></Icon>
