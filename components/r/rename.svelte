<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws0ombcdd.css';
import '../../css/t/t72impnyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws0ombcdd"/><path class="t72impnyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:rename" {...props}></Icon>
