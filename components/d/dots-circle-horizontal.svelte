<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4u4i6t9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4u4i6t9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dots-circle-horizontal" {...props}></Icon>
