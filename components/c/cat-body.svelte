<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4iudzo1t.css';
import '../../css/t/txqx25ycu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4iudzo1t"/><path class="txqx25ycu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cat-body" {...props}></Icon>
