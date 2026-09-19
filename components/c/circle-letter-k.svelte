<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7r2ne1tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r7r2ne1tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-k" {...props}></Icon>
