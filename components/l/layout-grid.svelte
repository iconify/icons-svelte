<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iam4o5jjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iam4o5jjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layout-grid" {...props}></Icon>
