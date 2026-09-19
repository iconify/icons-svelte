<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_rob8gfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="p_rob8gfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:forward-end" {...props}></Icon>
