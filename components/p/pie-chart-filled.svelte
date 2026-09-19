<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w37h81bqn.css';
import '../../css/c/ccl9t3mye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w37h81bqn"/><path class="ccl9t3mye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:pie-chart-filled" {...props}></Icon>
