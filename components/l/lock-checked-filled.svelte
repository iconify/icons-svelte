<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6vz2xq0h.css';
import '../../css/i/ii-9vg1fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6vz2xq0h"/><path class="ii-9vg1fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lock-checked-filled" {...props}></Icon>
