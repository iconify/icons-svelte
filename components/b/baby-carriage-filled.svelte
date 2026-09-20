<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt76-7y_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt76-7y_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:baby-carriage-filled" {...props}></Icon>
