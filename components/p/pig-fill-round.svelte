<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt_2g92wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt_2g92wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pig-fill-round" {...props}></Icon>
