<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duy3_oprs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duy3_oprs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alert-octagon" {...props}></Icon>
