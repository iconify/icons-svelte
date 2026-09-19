<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fimc63bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="fimc63bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fatarrowright" {...props}></Icon>
