<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq-lf_6bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq-lf_6bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:glasses-filled" {...props}></Icon>
