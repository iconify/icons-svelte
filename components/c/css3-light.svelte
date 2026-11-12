<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqn4acquj.css';
import '../../css/v/vr6lccbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqn4acquj"/><path class="vr6lccbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:css3-light" {...props}></Icon>
