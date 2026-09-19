<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t433r3pkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t433r3pkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:mention" {...props}></Icon>
