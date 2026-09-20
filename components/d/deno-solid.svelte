<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao7jv8aag.css';
import '../../css/o/ouxiombbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ao7jv8aag"/><path clip-rule="evenodd" class="ouxiombbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:deno-solid" {...props}></Icon>
