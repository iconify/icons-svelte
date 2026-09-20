<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckrfwua4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="ckrfwua4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hierarchy-1" {...props}></Icon>
