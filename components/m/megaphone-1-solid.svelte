<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia5v6ebka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ia5v6ebka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:megaphone-1-solid" {...props}></Icon>
