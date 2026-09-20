<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuj7w-b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iuj7w-b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:profile" {...props}></Icon>
