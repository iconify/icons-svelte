<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5w1ldbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5w1ldbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package" {...props}></Icon>
