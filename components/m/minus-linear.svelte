<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zov8t3bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zov8t3bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minus-linear" {...props}></Icon>
