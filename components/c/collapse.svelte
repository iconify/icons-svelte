<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsqbjmb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsqbjmb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:collapse" {...props}></Icon>
