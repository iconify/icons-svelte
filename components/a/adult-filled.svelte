<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gna62mbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gna62mbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adult-filled" {...props}></Icon>
