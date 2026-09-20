<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk9no8l7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk9no8l7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-down-fill" {...props}></Icon>
