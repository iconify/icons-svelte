<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad44kbbwp.css';
import '../../css/j/jf9rcrubp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ad44kbbwp"/><path class="jf9rcrubp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-photos" {...props}></Icon>
