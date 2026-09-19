<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahi6hlbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ahi6hlbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlefour" {...props}></Icon>
