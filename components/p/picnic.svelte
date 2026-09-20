<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovy1l4bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovy1l4bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:picnic" {...props}></Icon>
