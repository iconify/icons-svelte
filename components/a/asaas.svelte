<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndm8ctsqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":17};
const content = `<path class="ndm8ctsqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:asaas" {...props}></Icon>
