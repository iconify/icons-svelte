<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_31fsyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca_31fsyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-bold" {...props}></Icon>
