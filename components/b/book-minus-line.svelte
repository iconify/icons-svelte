<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp2kpl4oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp2kpl4oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:book-minus-line" {...props}></Icon>
