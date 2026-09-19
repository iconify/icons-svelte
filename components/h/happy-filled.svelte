<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9-ah5bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9-ah5bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:happy-filled" {...props}></Icon>
