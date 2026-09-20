<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uomcqqb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uomcqqb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:object-group" {...props}></Icon>
