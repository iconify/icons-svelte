<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omop2lbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="omop2lbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pictures-folder-memories-solid" {...props}></Icon>
