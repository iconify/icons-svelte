<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af04s8mfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="af04s8mfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lifeempty" {...props}></Icon>
