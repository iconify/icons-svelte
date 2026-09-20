<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nug6dobco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nug6dobco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kong" {...props}></Icon>
