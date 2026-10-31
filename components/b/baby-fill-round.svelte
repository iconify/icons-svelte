<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugy9pwbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugy9pwbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:baby-fill-round" {...props}></Icon>
