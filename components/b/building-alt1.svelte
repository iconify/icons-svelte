<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjzqn06_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pjzqn06_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:building-alt1" {...props}></Icon>
