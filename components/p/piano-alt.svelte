<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv6rrcc7g.css';
import '../../css/b/b7pa4ebgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv6rrcc7g"/><path class="b7pa4ebgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:piano-alt" {...props}></Icon>
