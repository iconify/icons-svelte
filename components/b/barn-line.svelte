<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsfik-bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsfik-bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:barn-line" {...props}></Icon>
