<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hon-ku8jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="hon-ku8jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:end" {...props}></Icon>
