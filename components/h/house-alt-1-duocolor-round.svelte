<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfxdh1bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfxdh1bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-1-duocolor-round" {...props}></Icon>
