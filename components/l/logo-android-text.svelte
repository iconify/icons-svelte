<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcgn2-byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xcgn2-byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-android-text" {...props}></Icon>
