<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc0n6teoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc0n6teoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mouse" {...props}></Icon>
