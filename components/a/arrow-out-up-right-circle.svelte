<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxyrztbdj.css';
import '../../css/h/h2egwczhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxyrztbdj"/><path class="h2egwczhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-right-circle" {...props}></Icon>
