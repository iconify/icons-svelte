<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjqachngk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjqachngk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloud-66" {...props}></Icon>
