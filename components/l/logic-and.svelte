<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw0t9gb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw0t9gb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:logic-and" {...props}></Icon>
