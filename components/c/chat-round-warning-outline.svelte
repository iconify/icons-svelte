<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsm1dmd4a.css';
import '../../css/z/z04quez4q.css';
import '../../css/x/x9024bb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsm1dmd4a"/><path class="z04quez4q"/><path clip-rule="evenodd" class="x9024bb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-warning-outline" {...props}></Icon>
