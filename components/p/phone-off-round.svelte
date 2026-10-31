<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ualn45blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ualn45blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:phone-off-round" {...props}></Icon>
