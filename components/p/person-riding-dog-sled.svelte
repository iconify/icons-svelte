<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo6ivfpgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eo6ivfpgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-dog-sled" {...props}></Icon>
