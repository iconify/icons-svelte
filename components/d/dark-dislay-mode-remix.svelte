<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4jtr84jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b4jtr84jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dark-dislay-mode-remix" {...props}></Icon>
