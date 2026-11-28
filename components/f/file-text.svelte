<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixe1kkbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixe1kkbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-text" {...props}></Icon>
