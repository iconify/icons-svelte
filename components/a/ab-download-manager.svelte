<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o80r8jpae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o80r8jpae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ab-download-manager" {...props}></Icon>
