<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk-6r4b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fk-6r4b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:autoflash" {...props}></Icon>
