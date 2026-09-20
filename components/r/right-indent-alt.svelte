<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbvrgpb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbvrgpb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:right-indent-alt" {...props}></Icon>
