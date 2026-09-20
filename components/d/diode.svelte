<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqq876bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqq876bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:diode" {...props}></Icon>
