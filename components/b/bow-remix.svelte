<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0i-87dsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m0i-87dsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bow-remix" {...props}></Icon>
