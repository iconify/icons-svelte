<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbe25ixpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nbe25ixpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-grin-tongue" {...props}></Icon>
