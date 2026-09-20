<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8p6y7blj.css';
import '../../css/m/ma5_rlb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f8p6y7blj"/><path clip-rule="evenodd" class="ma5_rlb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:c-sharp-solid" {...props}></Icon>
