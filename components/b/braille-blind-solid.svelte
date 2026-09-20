<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjl42vbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kjl42vbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:braille-blind-solid" {...props}></Icon>
