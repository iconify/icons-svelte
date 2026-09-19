<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfn3o34-i.css';
import '../../css/e/ecf1c0bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfn3o34-i"/><path class="ecf1c0bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:repositories" {...props}></Icon>
