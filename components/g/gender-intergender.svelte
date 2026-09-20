<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vves_obdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vves_obdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-intergender" {...props}></Icon>
