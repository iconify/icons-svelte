<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h20o60bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h20o60bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:globe-alt" {...props}></Icon>
