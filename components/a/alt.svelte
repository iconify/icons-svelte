<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6wlm125p.css';
import '../../css/m/m2_snib1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o6wlm125p"/><path class="m2_snib1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:alt" {...props}></Icon>
