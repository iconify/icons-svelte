<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1fanqb7g.css';
import '../../css/h/hxd1rr2uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1fanqb7g"/><path class="hxd1rr2uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:grs" {...props}></Icon>
