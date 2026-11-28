<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk51uq80h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk51uq80h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:laptop-alert" {...props}></Icon>
