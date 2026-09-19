<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwgygxbhr.css';
import '../../css/s/s4iurdf1n.css';
import '../../css/l/li1rn3ywo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwgygxbhr"/><path class="s4iurdf1n"/><path class="li1rn3ywo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-optimization-ai" {...props}></Icon>
