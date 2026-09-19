<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx488obmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx488obmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:openai" {...props}></Icon>
