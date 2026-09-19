<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6qay1xjw.css';
import '../../css/b/b0s1w34pd.css';
import '../../css/z/zmh5mjbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="s6qay1xjw"/><path class="b0s1w34pd"/><path class="zmh5mjbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-rotary-right-filled" {...props}></Icon>
