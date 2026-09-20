<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg_t2jbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg_t2jbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-2-filled" {...props}></Icon>
