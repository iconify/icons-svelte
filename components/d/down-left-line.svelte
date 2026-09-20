<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iikt1teqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iikt1teqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:down-left-line" {...props}></Icon>
