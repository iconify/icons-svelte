<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdd82p7ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdd82p7ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fortress" {...props}></Icon>
