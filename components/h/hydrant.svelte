<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2sbr4uqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="q2sbr4uqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hydrant" {...props}></Icon>
