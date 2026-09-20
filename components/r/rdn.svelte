<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xra98m7aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xra98m7aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rdn" {...props}></Icon>
