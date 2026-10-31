<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_15pbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae_15pbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pause-round" {...props}></Icon>
