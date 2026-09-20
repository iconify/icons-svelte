<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3bji0brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3bji0brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apache" {...props}></Icon>
