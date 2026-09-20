<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12i2fc3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i12i2fc3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cryengine" {...props}></Icon>
