<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giv9vwr2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4.5};
const content = `<path class="giv9vwr2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:dashboard-f" {...props}></Icon>
