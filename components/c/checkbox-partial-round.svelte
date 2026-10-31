<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msi2722la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msi2722la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:checkbox-partial-round" {...props}></Icon>
