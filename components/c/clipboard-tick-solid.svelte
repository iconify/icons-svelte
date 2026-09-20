<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzws48i-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="gzws48i-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-tick-solid" {...props}></Icon>
