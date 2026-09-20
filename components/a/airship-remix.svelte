<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qujgu5bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qujgu5bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:airship-remix" {...props}></Icon>
