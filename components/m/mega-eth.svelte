<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwzpwfbbu.css';
import '../../css/r/ri95jlkhc.css';
import '../../css/a/avb8i1b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gwzpwfbbu"/><path clip-rule="evenodd" class="ri95jlkhc"/><path class="avb8i1b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mega-eth" {...props}></Icon>
