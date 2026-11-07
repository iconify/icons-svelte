<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn48e2bxu.css';
import '../../css/q/qe1l0xb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn48e2bxu"/><path class="qe1l0xb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:muted-outline" {...props}></Icon>
