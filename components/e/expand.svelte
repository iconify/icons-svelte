<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8p3x7bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8p3x7bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:expand" {...props}></Icon>
