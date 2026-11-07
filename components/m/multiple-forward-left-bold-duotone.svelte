<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ybt1sxt.css';
import '../../css/s/st7xg9lhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ybt1sxt"/><path clip-rule="evenodd" class="st7xg9lhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:multiple-forward-left-bold-duotone" {...props}></Icon>
