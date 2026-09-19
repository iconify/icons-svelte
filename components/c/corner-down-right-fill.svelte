<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mok1onfec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mok1onfec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:corner-down-right-fill" {...props}></Icon>
