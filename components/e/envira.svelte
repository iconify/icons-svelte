<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehs67ebsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ehs67ebsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:envira" {...props}></Icon>
