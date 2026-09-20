<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoimc4blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoimc4blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:moon-fill" {...props}></Icon>
