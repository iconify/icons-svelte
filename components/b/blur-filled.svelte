<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r21hqhwrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r21hqhwrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:blur-filled" {...props}></Icon>
