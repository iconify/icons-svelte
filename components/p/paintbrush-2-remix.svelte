<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tttppzn-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tttppzn-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:paintbrush-2-remix" {...props}></Icon>
