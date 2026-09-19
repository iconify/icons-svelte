<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecsbwkq3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ecsbwkq3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ban-smoking" {...props}></Icon>
