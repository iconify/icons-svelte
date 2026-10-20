<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jur6qbc2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jur6qbc2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:fingerprint-pattern" {...props}></Icon>
