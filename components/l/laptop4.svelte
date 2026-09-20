<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlvnlqb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlvnlqb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop4" {...props}></Icon>
