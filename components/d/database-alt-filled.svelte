<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw14v029a.css';
import '../../css/r/r3-2ecc9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw14v029a"/><path class="r3-2ecc9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:database-alt-filled" {...props}></Icon>
