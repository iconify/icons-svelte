<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux20_bc-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ux20_bc-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-percent-sharp-fill" {...props}></Icon>
