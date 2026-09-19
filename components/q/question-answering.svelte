<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcunifpot.css';
import '../../css/z/zgaui9bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xcunifpot"/><path class="zgaui9bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:question-answering" {...props}></Icon>
