<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1eoneb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":767,"height":1024};
const content = `<path class="l1eoneb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:rouble" {...props}></Icon>
