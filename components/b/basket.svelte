<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjngo4b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjngo4b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:basket" {...props}></Icon>
