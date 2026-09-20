<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_xhv5c_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_xhv5c_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-dashed-check-fill" {...props}></Icon>
