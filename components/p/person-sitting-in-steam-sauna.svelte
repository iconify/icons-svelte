<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei34isb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ei34isb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-in-steam-sauna" {...props}></Icon>
