<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-xfl32fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v-xfl32fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:no-bicycles" {...props}></Icon>
