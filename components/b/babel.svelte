<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfz452bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jfz452bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:babel" {...props}></Icon>
