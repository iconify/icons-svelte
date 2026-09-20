<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0mywfpde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0mywfpde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:niantic" {...props}></Icon>
