<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvj4ouunw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cvj4ouunw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:printer-remix" {...props}></Icon>
