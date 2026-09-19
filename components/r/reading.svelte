<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqd17fbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqd17fbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reading" {...props}></Icon>
