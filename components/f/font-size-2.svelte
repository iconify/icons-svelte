<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onavo181g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onavo181g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:font-size-2" {...props}></Icon>
