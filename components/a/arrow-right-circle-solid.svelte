<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbh2wzl7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rbh2wzl7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-right-circle-solid" {...props}></Icon>
