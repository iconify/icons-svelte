<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aev39tqol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="aev39tqol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-mediaencoder" {...props}></Icon>
