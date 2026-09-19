<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf7pp8qih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qf7pp8qih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-landscape" {...props}></Icon>
