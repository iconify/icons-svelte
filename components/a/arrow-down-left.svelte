<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iizhlp7_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iizhlp7_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-left" {...props}></Icon>
