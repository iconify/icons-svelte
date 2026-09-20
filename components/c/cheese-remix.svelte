<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu-373zuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yu-373zuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cheese-remix" {...props}></Icon>
