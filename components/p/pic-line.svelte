<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvsatfkmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvsatfkmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-line" {...props}></Icon>
