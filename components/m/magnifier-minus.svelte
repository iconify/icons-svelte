<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nve8_x58c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nve8_x58c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:magnifier-minus" {...props}></Icon>
