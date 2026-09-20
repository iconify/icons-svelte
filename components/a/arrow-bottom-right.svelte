<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hradpqb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="hradpqb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:arrow-bottom-right" {...props}></Icon>
