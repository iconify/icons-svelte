<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntd1ge7ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntd1ge7ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:citrix" {...props}></Icon>
