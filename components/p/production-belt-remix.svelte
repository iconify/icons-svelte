<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-5hvoban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d-5hvoban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:production-belt-remix" {...props}></Icon>
