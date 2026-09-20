<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwg-gc-pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwg-gc-pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:derspiegel" {...props}></Icon>
