<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5ch-dc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5ch-dc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-left-02" {...props}></Icon>
