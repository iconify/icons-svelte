<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1roj-3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="in1roj-3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cao-dai-remix" {...props}></Icon>
