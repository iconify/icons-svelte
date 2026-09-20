<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm19ivbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm19ivbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-h" {...props}></Icon>
