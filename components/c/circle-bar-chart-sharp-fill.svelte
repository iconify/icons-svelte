<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p69jomuhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p69jomuhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-sharp-fill" {...props}></Icon>
