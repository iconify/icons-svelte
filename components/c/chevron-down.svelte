<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6dbjw9zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="x6dbjw9zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chevron-down" {...props}></Icon>
