<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwls6usiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwls6usiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cryptpad" {...props}></Icon>
