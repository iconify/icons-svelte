<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxk4400ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xxk4400ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:link" {...props}></Icon>
