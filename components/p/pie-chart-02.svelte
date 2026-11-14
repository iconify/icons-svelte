<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhtg36b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhtg36b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pie-chart-02" {...props}></Icon>
