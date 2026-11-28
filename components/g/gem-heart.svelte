<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dab_wmkpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dab_wmkpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gem-heart" {...props}></Icon>
