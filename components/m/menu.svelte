<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq6bcbctw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="iq6bcbctw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:menu" {...props}></Icon>
