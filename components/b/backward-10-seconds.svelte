<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/i5oofwb9h.css';
import '../../css/i/i5tsyvxih.css';
import '../../css/h/hdc8gxnie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5oofwb9h"/><path class="i5tsyvxih"/><path class="hdc8gxnie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:backward-10-seconds" {...props}></Icon>
