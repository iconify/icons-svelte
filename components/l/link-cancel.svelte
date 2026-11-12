<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l36mhpb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l36mhpb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-cancel" {...props}></Icon>
