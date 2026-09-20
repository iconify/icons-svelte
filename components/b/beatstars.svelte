<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6c2ulpvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6c2ulpvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:beatstars" {...props}></Icon>
