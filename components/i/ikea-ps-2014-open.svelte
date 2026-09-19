<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_o4u3b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_o4u3b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-ps-2014-open" {...props}></Icon>
