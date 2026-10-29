<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc7r9_r6i.css';
import '../../css/p/pzwkoob0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7r9_r6i"/><path class="pzwkoob0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:activity" {...props}></Icon>
