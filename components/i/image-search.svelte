<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocxedjb1h.css';
import '../../css/h/hh28l1bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocxedjb1h"/><path class="hh28l1bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-search" {...props}></Icon>
