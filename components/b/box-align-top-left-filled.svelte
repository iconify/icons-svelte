<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqb5wb4we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqb5wb4we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-top-left-filled" {...props}></Icon>
