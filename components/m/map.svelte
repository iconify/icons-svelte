<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhok3cb9s.css';
import '../../css/o/ob_nbubvj.css';
import '../../css/m/m2huwebvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yhok3cb9s"/><circle class="ob_nbubvj"/><path class="m2huwebvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:map" {...props}></Icon>
