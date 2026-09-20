<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8z63cb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q8z63cb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:diagonal-triangle-arrow-2-remix" {...props}></Icon>
