<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpjvikbjg.css';
import '../../css/g/gleiq_5ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gpjvikbjg"/><path class="gleiq_5ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-kubernetes" {...props}></Icon>
