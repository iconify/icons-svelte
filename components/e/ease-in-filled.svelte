<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjh1g7rma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjh1g7rma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ease-in-filled" {...props}></Icon>
