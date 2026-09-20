<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnxzfjb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cnxzfjb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-on-parking-line" {...props}></Icon>
