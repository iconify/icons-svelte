<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd9z98brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd9z98brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:linkfire" {...props}></Icon>
