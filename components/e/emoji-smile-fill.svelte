<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3vmb7bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u3vmb7bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-smile-fill" {...props}></Icon>
