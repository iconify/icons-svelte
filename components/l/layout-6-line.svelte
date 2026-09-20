<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnh_2wb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnh_2wb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-6-line" {...props}></Icon>
