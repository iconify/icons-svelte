<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chp57gsgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chp57gsgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pause-circle" {...props}></Icon>
