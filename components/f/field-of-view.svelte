<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df7_jw1qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="df7_jw1qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:field-of-view" {...props}></Icon>
