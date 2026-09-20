<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwdbhvfaz.css';
import '../../css/x/xj-vmnbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwdbhvfaz"/><path class="xj-vmnbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ggg" {...props}></Icon>
