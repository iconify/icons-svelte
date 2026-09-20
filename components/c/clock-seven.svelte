<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_li8cc6d.css';
import '../../css/t/t9ck36orq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_li8cc6d"/><path class="t9ck36orq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clock-seven" {...props}></Icon>
