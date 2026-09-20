<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xztuxob4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xztuxob4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:new-york-times" {...props}></Icon>
