<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahqll4bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ahqll4bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bin-solid" {...props}></Icon>
