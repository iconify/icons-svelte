<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_nnus9hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q_nnus9hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:printer" {...props}></Icon>
