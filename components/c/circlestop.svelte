<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv1trmbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qv1trmbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlestop" {...props}></Icon>
