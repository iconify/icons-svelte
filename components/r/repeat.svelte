<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_4_9lhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1_4_9lhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:repeat" {...props}></Icon>
