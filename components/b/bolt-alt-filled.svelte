<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv-3-ac2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv-3-ac2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bolt-alt-filled" {...props}></Icon>
