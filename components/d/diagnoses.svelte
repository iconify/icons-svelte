<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2a_qteud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g2a_qteud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:diagnoses" {...props}></Icon>
