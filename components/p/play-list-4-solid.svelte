<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q75qm4lmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q75qm4lmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:play-list-4-solid" {...props}></Icon>
