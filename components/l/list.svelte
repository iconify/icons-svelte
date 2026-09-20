<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj46sjb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj46sjb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:list" {...props}></Icon>
