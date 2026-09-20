<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_8gb412d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f_8gb412d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:feather-pen-remix" {...props}></Icon>
