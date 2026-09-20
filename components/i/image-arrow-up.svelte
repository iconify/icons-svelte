<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmh3rlnos.css';
import '../../css/d/dazc8w85q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmh3rlnos"/><path class="dazc8w85q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-arrow-up" {...props}></Icon>
