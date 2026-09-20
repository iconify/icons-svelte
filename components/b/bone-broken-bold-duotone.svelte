<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itet59rhp.css';
import '../../css/k/kdn9gsbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itet59rhp"/><path class="kdn9gsbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bone-broken-bold-duotone" {...props}></Icon>
