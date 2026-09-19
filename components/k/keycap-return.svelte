<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ed7nb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a3ed7nb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-return" {...props}></Icon>
