<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlu42j8ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlu42j8ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:git-merge-filled" {...props}></Icon>
