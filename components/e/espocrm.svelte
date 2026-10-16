<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe1t213fe.css';
import '../../css/o/o3xf0rsxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8.467,"height":8.467};
const content = `<circle class="fe1t213fe"/><path class="o3xf0rsxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:espocrm" {...props}></Icon>
