<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqn4acquj.css';
import '../../css/e/eyi6n2idh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqn4acquj"/><path class="eyi6n2idh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:css3-light" {...props}></Icon>
