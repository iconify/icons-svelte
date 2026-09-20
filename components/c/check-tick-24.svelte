<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9_696beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9_696beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:check-tick-24" {...props}></Icon>
