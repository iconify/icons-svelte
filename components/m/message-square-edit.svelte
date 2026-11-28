<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvo6y868r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvo6y868r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square-edit" {...props}></Icon>
