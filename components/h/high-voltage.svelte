<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovis36bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovis36bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:high-voltage" {...props}></Icon>
