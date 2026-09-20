<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9owu2hrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s9owu2hrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:application-add-solid" {...props}></Icon>
