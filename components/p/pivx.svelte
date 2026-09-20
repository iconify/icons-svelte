<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4ouod96n.css';
import '../../css/d/dcpdfk6aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4ouod96n"/><path class="dcpdfk6aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pivx" {...props}></Icon>
