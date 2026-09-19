<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq4pumlsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fq4pumlsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cursor-text" {...props}></Icon>
