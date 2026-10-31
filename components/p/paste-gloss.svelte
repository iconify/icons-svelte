<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6h7saccw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6h7saccw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paste-gloss" {...props}></Icon>
