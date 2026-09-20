<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej5e9xjrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ej5e9xjrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:gold-remix" {...props}></Icon>
