<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riurxjb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="riurxjb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-then-curving-up-arrow-small" {...props}></Icon>
