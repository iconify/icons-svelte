<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm-5mp_fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mm-5mp_fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:briefcase" {...props}></Icon>
