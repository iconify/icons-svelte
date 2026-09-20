<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4x1bs.css';
import '../../css/n/ntj7kf.css';
import '../../css/d/d-jkxijw.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4x1bs"/><circle class="ntj7kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:map-marker-alt" {...props}></Icon>
