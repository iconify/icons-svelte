<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3c7cyvll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q3c7cyvll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-right-arrow-up-left" {...props}></Icon>
