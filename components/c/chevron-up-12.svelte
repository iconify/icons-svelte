<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu5cqxbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="fu5cqxbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-up-12" {...props}></Icon>
