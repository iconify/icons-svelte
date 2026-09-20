<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgo9_nczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgo9_nczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ipfs" {...props}></Icon>
