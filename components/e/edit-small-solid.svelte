<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9163i5se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h9163i5se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:edit-small-solid" {...props}></Icon>
