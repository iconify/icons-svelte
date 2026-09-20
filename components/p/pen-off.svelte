<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a50pz2beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a50pz2beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pen-off" {...props}></Icon>
