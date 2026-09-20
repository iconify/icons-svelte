<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whv0_vrmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whv0_vrmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hsbc" {...props}></Icon>
