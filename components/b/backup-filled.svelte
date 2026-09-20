<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a615a3b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a615a3b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:backup-filled" {...props}></Icon>
