<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_1r2ws4u.css';
import '../../css/a/a1kinh57h.css';
import '../../css/q/quj0hibon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_1r2ws4u"/><circle class="a1kinh57h"/><path class="quj0hibon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cycling" {...props}></Icon>
