<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx_x1jbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx_x1jbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-left-box-fill" {...props}></Icon>
