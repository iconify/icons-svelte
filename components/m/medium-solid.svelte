<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qya48qbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qya48qbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:medium-solid" {...props}></Icon>
