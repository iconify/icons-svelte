<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gas0o7beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gas0o7beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:check-shape" {...props}></Icon>
