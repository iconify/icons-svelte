<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am65ptyzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="am65ptyzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:code-solid" {...props}></Icon>
