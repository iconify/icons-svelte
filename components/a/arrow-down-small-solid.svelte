<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtl2yqw5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qtl2yqw5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-down-small-solid" {...props}></Icon>
