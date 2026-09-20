<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2n5zgbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2n5zgbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-left-24" {...props}></Icon>
