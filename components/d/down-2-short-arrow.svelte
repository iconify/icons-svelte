<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb-n7kb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-n7kb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:down-2-short-arrow" {...props}></Icon>
