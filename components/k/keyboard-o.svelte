<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm2clvi6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1280};
const content = `<path class="cm2clvi6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:keyboard-o" {...props}></Icon>
