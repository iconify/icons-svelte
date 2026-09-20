<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtghustnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xtghustnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-right-small-solid" {...props}></Icon>
