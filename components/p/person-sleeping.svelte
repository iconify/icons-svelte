<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8w3bmb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z8w3bmb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sleeping" {...props}></Icon>
