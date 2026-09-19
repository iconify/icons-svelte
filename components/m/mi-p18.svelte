<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddj9ktb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddj9ktb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mi-p18" {...props}></Icon>
