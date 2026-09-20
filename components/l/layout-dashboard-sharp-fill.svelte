<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on9qdlkrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on9qdlkrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layout-dashboard-sharp-fill" {...props}></Icon>
