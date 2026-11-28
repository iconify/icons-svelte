<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdgpambfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdgpambfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-to-line-solid" {...props}></Icon>
