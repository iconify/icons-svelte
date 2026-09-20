<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfv8tcc4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sfv8tcc4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:health-care-2-solid" {...props}></Icon>
