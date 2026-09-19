<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8a072jfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h8a072jfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-option-small" {...props}></Icon>
