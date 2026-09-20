<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xir71cb7c.css';
import '../../css/n/n6l7qezyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xir71cb7c"/><path class="n6l7qezyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-diff-24" {...props}></Icon>
