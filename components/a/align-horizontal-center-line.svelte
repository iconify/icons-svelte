<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v95x24b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v95x24b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:align-horizontal-center-line" {...props}></Icon>
