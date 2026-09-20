<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_1jzeb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_1jzeb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-down-sharp-fill" {...props}></Icon>
