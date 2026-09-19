<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1yn3jcfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q1yn3jcfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:readme" {...props}></Icon>
