<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iypj7136t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iypj7136t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coughing-face" {...props}></Icon>
