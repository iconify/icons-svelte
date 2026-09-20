<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyoei_wsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyoei_wsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pelican" {...props}></Icon>
