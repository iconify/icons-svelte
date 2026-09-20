<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgj-x05-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgj-x05-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-column-stacked-sharp" {...props}></Icon>
