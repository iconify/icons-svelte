<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6lmsxb0c.css';
import '../../css/t/thp3xzwhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6lmsxb0c"/><path class="thp3xzwhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:meat" {...props}></Icon>
