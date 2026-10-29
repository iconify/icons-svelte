<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci2_dx6ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci2_dx6ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-6" {...props}></Icon>
