<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5rlfsumx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5rlfsumx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:medical-cross" {...props}></Icon>
