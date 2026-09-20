<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_3l2v-ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_3l2v-ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-trending-up-sharp-fill" {...props}></Icon>
