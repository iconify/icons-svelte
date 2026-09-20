<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyhsjn3zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyhsjn3zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-g-small" {...props}></Icon>
