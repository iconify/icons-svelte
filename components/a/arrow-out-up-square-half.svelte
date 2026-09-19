<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bot9nzqtg.css';
import '../../css/o/o04p_sbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bot9nzqtg"/><path class="o04p_sbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-square-half" {...props}></Icon>
