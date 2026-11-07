<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuf9y1byy.css';
import '../../css/o/oo7eexbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuf9y1byy"/><path class="oo7eexbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forbidden-bold" {...props}></Icon>
