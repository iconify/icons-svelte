<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-pxawmvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-pxawmvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-cursor-sharp-fill" {...props}></Icon>
