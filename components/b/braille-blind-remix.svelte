<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezsce_bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ezsce_bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:braille-blind-remix" {...props}></Icon>
