<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m21j3qb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m21j3qb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bullet-list-solid" {...props}></Icon>
