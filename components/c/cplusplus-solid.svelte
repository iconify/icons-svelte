<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n004xq-kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n004xq-kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cplusplus-solid" {...props}></Icon>
