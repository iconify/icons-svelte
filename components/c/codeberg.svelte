<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwot3iucy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwot3iucy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codeberg" {...props}></Icon>
