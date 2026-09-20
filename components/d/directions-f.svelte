<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pex-d5__n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="pex-d5__n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:directions-f" {...props}></Icon>
