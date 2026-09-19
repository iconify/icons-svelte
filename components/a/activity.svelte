<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgjcbobyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dgjcbobyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:activity" {...props}></Icon>
