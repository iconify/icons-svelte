<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivkcne5yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivkcne5yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pentagon-off" {...props}></Icon>
