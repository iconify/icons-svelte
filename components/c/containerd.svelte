<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlfmv5tdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlfmv5tdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:containerd" {...props}></Icon>
