<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdm9qq6xg.css';
import '../../css/u/uuqt_yb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdm9qq6xg"/><path class="uuqt_yb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:info-circle" {...props}></Icon>
