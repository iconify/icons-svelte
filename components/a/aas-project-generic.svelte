<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwb-hxokg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwb-hxokg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-generic" {...props}></Icon>
