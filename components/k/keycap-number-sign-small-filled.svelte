<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4b2i8bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u4b2i8bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-number-sign-small-filled" {...props}></Icon>
