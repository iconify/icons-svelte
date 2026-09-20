<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwsh51bpk.css';
import '../../css/u/ungwd2b5z.css';
import '../../css/r/rj032db8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwsh51bpk"/><path class="ungwd2b5z"/><path class="rj032db8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-branch-24" {...props}></Icon>
