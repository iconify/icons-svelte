<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vro_2gb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vro_2gb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circles-sharp" {...props}></Icon>
