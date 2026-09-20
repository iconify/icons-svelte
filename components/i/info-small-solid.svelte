<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wazcg0b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wazcg0b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:info-small-solid" {...props}></Icon>
