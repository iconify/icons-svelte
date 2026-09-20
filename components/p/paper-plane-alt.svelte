<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2q2m8bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="r2q2m8bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:paper-plane-alt" {...props}></Icon>
