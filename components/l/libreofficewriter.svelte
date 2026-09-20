<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubynd95be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubynd95be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:libreofficewriter" {...props}></Icon>
