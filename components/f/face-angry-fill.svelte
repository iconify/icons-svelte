<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxti38ops.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxti38ops"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-angry-fill" {...props}></Icon>
