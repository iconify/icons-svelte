<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he8gb17ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="he8gb17ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:page-setting-remix" {...props}></Icon>
