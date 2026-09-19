<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgzpk6fcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="rgzpk6fcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:female" {...props}></Icon>
