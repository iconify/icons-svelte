<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu43tbcgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fu43tbcgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:keyboard-option-setting-gear-solid" {...props}></Icon>
