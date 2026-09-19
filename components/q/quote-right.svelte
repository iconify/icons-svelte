<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avfn-hboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avfn-hboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-right" {...props}></Icon>
