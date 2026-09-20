<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg882nbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jg882nbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:redwoodjs-solid" {...props}></Icon>
