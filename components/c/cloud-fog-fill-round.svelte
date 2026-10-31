<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd96-8ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgd96-8ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-fog-fill-round" {...props}></Icon>
