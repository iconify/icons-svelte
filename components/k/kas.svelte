<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyuucx0_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyuucx0_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kas" {...props}></Icon>
