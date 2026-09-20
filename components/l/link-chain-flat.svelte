<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe9-4qb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xe9-4qb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:link-chain-flat" {...props}></Icon>
