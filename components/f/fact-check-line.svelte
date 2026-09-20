<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po936mb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po936mb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:fact-check-line" {...props}></Icon>
