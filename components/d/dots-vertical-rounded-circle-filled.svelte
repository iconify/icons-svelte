<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-9sglb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-9sglb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dots-vertical-rounded-circle-filled" {...props}></Icon>
