<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhmbx9-pc.css';
import '../../css/w/w92r8zftn.css';
import '../../css/v/v3w7a-bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lhmbx9-pc"/><path class="w92r8zftn"/><path class="v3w7a-bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:newrelic" {...props}></Icon>
