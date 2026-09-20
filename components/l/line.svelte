<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i65jm5bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="i65jm5bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:line" {...props}></Icon>
