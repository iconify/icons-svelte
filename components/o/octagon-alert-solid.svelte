<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5jbh9b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5jbh9b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:octagon-alert-solid" {...props}></Icon>
