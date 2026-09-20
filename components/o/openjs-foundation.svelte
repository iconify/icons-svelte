<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa32-bcua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa32-bcua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openjs-foundation" {...props}></Icon>
