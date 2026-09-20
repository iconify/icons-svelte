<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w43g67bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w43g67bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coppel" {...props}></Icon>
