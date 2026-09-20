<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5546eb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5546eb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:arrow-right-long" {...props}></Icon>
