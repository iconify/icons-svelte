<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6c158b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6c158b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:kayak" {...props}></Icon>
