<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx9x8pb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sx9x8pb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:phidata" {...props}></Icon>
