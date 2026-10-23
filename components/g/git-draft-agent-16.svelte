<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odvyybvbi.css';
import '../../css/b/b2gj-9bfn.css';
import '../../css/c/c_sefrbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="odvyybvbi"/><path class="b2gj-9bfn"/><path class="c_sefrbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-draft-agent-16" {...props}></Icon>
