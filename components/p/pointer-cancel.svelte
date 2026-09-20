<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i33b-_9mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i33b-_9mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-cancel" {...props}></Icon>
