<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw05iib2q.css';
import '../../css/n/n8h410f2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw05iib2q"/><path clip-rule="evenodd" class="n8h410f2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:paribu" {...props}></Icon>
