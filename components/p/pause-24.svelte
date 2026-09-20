<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n75uy8bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n75uy8bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pause-24" {...props}></Icon>
