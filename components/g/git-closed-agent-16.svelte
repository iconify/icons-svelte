<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igkh1jbmt.css';
import '../../css/b/b166yvpks.css';
import '../../css/u/u8zlrzbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="igkh1jbmt"/><path class="b166yvpks"/><path class="u8zlrzbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-closed-agent-16" {...props}></Icon>
