<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq3pidbpg.css';
import '../../css/l/l93btfbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq3pidbpg"/><path class="l93btfbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dryer-filled" {...props}></Icon>
