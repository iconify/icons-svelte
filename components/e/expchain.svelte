<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-4r5ndkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-4r5ndkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:expchain" {...props}></Icon>
