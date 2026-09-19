<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9sh_qbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9sh_qbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:down-right-arrow" {...props}></Icon>
