<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa96asbwu.css';
import '../../css/n/nt80sb9do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa96asbwu"/><path clip-rule="evenodd" class="nt80sb9do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:globe-solid" {...props}></Icon>
