<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsx-hsbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsx-hsbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:actix" {...props}></Icon>
