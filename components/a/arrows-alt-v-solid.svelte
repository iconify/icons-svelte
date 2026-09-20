<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8chywiab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d8chywiab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrows-alt-v-solid" {...props}></Icon>
