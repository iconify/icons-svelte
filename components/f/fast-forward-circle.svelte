<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwibdw4bb.css';
import '../../css/y/ynj1yft6n.css';
import '../../css/x/x6pvdjbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="ynj1yft6n"/><path class="x6pvdjbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fast-forward-circle" {...props}></Icon>
