<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt-gltsgq.css';
import '../../css/e/eb4ipfkkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt-gltsgq"/><path class="eb4ipfkkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rename" {...props}></Icon>
