<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6liw8z9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6liw8z9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:link" {...props}></Icon>
