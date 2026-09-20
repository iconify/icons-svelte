<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or5y5jvbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or5y5jvbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-drizzle" {...props}></Icon>
