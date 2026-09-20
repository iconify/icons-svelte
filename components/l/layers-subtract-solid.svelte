<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j20ns8dno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="j20ns8dno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-subtract-solid" {...props}></Icon>
