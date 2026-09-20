<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi46hz2yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fi46hz2yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:elixir-16" {...props}></Icon>
