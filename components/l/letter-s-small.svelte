<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q51aqy70n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q51aqy70n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-s-small" {...props}></Icon>
