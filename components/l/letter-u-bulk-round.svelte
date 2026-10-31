<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4v-ekbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4v-ekbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-u-bulk-round" {...props}></Icon>
