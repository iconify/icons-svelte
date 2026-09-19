<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywize-p9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywize-p9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:desk-for-laptop" {...props}></Icon>
