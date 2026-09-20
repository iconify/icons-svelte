<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju_8lzt-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ju_8lzt-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-down-fill" {...props}></Icon>
