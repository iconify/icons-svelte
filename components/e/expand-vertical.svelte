<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc4op3bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc4op3bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:expand-vertical" {...props}></Icon>
