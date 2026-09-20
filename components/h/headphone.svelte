<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx9bq6bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rx9bq6bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:headphone" {...props}></Icon>
