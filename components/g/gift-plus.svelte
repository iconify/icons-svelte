<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt4un_bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt4un_bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gift-plus" {...props}></Icon>
