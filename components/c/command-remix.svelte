<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny36t5b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ny36t5b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:command-remix" {...props}></Icon>
