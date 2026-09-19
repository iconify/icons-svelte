<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jde3g9ndn.css';
import '../../css/j/j4z_4jizz.css';
import '../../css/g/ghwhkkblu.css';
import '../../css/s/snx15u1zl.css';
import '../../css/w/w7gkj6r1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jde3g9ndn"/><path class="j4z_4jizz"/><path class="ghwhkkblu"/><path class="snx15u1zl"/><path class="w7gkj6r1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cheese-cake-02" {...props}></Icon>
