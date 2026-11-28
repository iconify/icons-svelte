<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehe98ehnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehe98ehnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:phone-outgoing" {...props}></Icon>
