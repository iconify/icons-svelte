<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9qr0pwdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="a9qr0pwdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:heart-circle-solid" {...props}></Icon>
