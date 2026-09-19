<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7e247bcz.css';
import '../../css/w/wtmn1wb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7e247bcz"/><path class="wtmn1wb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alert-circle" {...props}></Icon>
