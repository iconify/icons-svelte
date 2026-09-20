<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wntenublw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wntenublw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:morning" {...props}></Icon>
