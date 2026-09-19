<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcse9kmkw.css';
import '../../css/e/e54jf8rbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jcse9kmkw"/><path class="e54jf8rbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:blogger2" {...props}></Icon>
