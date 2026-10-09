<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq-3jutph.css';
import '../../css/t/t2dpk9bzd.css';
import '../../css/a/aqnz63b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gq-3jutph"/><path class="t2dpk9bzd"/><path class="aqnz63b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cooking-pot-48" {...props}></Icon>
