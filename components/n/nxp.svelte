<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg4rw_iiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg4rw_iiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nxp" {...props}></Icon>
