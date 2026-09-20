<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgaltbb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lgaltbb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pen-1-solid" {...props}></Icon>
