<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5npjt0gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5npjt0gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-filled" {...props}></Icon>
