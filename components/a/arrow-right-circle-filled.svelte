<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqbaauboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqbaauboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right-circle-filled" {...props}></Icon>
