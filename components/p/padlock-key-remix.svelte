<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oha-rb4et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oha-rb4et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:padlock-key-remix" {...props}></Icon>
