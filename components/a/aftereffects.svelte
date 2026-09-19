<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe2kkz7uf.css';
import '../../css/d/dbikkebwp.css';
import '../../css/m/ms5yux87p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qe2kkz7uf"/><path class="dbikkebwp"/><path class="ms5yux87p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:aftereffects" {...props}></Icon>
