<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2bxbq90f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f2bxbq90f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:code-filled" {...props}></Icon>
