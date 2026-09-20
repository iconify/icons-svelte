<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h71f35jbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h71f35jbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layout-dashboard" {...props}></Icon>
