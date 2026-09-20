<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phh9mqbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phh9mqbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:minimize-2" {...props}></Icon>
