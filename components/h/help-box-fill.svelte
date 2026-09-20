<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7mqcobyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z7mqcobyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:help-box-fill" {...props}></Icon>
