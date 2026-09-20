<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ket0p1bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ket0p1bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mntc" {...props}></Icon>
