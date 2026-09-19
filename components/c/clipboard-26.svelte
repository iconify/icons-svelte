<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufjhs5b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ufjhs5b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-26" {...props}></Icon>
