<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy27c67ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy27c67ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:course-up-linear" {...props}></Icon>
