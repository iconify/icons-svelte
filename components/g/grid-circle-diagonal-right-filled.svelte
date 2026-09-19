<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3ehty72y.css';
import '../../css/n/neukm1fuz.css';
import '../../css/g/gtn46m-jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3ehty72y"/><rect class="neukm1fuz"/><rect class="gtn46m-jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle-diagonal-right-filled" {...props}></Icon>
