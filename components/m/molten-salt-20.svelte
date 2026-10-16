<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqfw9ounj.css';
import '../../css/v/v9iy7tbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gqfw9ounj"/><path class="v9iy7tbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:molten-salt-20" {...props}></Icon>
