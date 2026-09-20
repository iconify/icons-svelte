<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk6fksicr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uk6fksicr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:flip-horizontal-solid" {...props}></Icon>
