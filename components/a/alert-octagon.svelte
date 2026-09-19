<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dstdqz7pa.css';
import '../../css/p/prmb0_bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dstdqz7pa duoicon-secondary-layer"/><path class="duoicon-primary-layer prmb0_bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:alert-octagon" {...props}></Icon>
