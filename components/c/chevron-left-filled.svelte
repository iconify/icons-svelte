<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9-_irbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9-_irbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevron-left-filled" {...props}></Icon>
