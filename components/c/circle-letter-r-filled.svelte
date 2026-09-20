<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0srv8qcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0srv8qcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-r-filled" {...props}></Icon>
