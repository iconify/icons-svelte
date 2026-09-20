<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1o8mdb_p.css';
import '../../css/t/twm3r6b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l1o8mdb_p"/><path clip-rule="evenodd" class="twm3r6b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pin-solid" {...props}></Icon>
