<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pns5a3bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pns5a3bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cost-estimate-solid" {...props}></Icon>
