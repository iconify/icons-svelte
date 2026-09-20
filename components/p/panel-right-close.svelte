<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ce2nkfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ce2nkfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-close" {...props}></Icon>
