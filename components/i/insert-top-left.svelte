<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou8ds1baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ou8ds1baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:insert-top-left" {...props}></Icon>
