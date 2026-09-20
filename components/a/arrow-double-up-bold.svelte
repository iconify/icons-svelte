<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehf9i8bjq.css';
import '../../css/k/k5x1h1nos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehf9i8bjq"/><path class="k5x1h1nos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-double-up-bold" {...props}></Icon>
