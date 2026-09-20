<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c06y5ub8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c06y5ub8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-meh-20-solid" {...props}></Icon>
