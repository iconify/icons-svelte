<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uniwpj3nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":117,"height":116};
const content = `<path clip-rule="evenodd" class="uniwpj3nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kibo-ui-light" {...props}></Icon>
