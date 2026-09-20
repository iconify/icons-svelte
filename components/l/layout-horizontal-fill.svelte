<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imbkg0n5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imbkg0n5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-horizontal-fill" {...props}></Icon>
