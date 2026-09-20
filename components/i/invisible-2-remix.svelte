<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh-kbll_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gh-kbll_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:invisible-2-remix" {...props}></Icon>
