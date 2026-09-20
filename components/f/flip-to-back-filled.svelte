<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m363_p6yk.css';
import '../../css/q/q9ju5jb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m363_p6yk"/><path class="q9ju5jb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flip-to-back-filled" {...props}></Icon>
