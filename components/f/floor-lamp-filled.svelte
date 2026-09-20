<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mccejepmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mccejepmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:floor-lamp-filled" {...props}></Icon>
