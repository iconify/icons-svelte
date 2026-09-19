<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj8wdoo8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj8wdoo8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:comment-02" {...props}></Icon>
