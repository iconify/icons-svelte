<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jopm6tb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jopm6tb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:apache-flink" {...props}></Icon>
