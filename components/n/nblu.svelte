<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccfj3dt4e.css';
import '../../css/g/gps6u6bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccfj3dt4e"/><path class="gps6u6bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nblu" {...props}></Icon>
