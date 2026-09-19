<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-0trnsix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="m-0trnsix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:rdio" {...props}></Icon>
