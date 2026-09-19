<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbez4kq0u.css';
import '../../css/g/gfk4z3biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbez4kq0u"/><path class="gfk4z3biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-x" {...props}></Icon>
