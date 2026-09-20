<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgdqlgm9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgdqlgm9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:comsol" {...props}></Icon>
