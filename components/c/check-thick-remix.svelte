<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndqkclbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ndqkclbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:check-thick-remix" {...props}></Icon>
