<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twoyz1r4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twoyz1r4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-sun-sharp" {...props}></Icon>
