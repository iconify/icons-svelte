<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqayco94q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqayco94q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-left" {...props}></Icon>
