<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq_3ltbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq_3ltbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-up-right-dashed-panel-sharp-fill" {...props}></Icon>
