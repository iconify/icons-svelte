<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkiwhgb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dkiwhgb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:belgium" {...props}></Icon>
