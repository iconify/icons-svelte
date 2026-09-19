<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s1990xb8r.css';
import '../../css/o/oiu-3i4pj.css';
import '../../css/s/s5n1v6bqp.css';
import '../../css/w/wwr7j0b1g.css';
import '../../css/p/p290x8bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s1990xb8r"/><path class="oiu-3i4pj"/><path class="s5n1v6bqp"/><path class="wwr7j0b1g"/><path class="p290x8bhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lock-computer" {...props}></Icon>
