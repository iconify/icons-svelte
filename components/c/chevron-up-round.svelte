<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2_9zfvmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e2_9zfvmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:chevron-up-round" {...props}></Icon>
