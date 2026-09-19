<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arx939g8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="arx939g8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-eight-small-filled" {...props}></Icon>
