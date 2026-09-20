<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekryy-mie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekryy-mie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:crop-line" {...props}></Icon>
