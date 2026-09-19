<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaev_d16p.css';
import '../../css/a/a8l7vd6df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="zaev_d16p"/><rect class="a8l7vd6df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pause-filled" {...props}></Icon>
