<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5x23nlau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5x23nlau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brightness-off" {...props}></Icon>
