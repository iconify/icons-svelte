<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn92h86ac.css';
import '../../css/v/v8a66ebgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn92h86ac"/><path class="v8a66ebgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-to-line-bold-duotone" {...props}></Icon>
