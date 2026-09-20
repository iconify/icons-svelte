<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/supp6dp9b.css';
import '../../css/z/za-azub4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="supp6dp9b"/><path class="za-azub4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bico" {...props}></Icon>
