<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pst0mi77l.css';
import '../../css/b/bhja3k33r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pst0mi77l"/><path class="bhja3k33r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cog-duotone" {...props}></Icon>
