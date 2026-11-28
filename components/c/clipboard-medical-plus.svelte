<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw1kw4huw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw1kw4huw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-medical-plus" {...props}></Icon>
