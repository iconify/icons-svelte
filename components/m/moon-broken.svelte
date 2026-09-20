<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyk1n58rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyk1n58rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-broken" {...props}></Icon>
