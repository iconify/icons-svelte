<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/we9b9_p-a.css';
import '../../css/q/qzzo5nbdd.css';
import '../../css/x/xcrrugbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="we9b9_p-a"/><path class="qzzo5nbdd"/><path class="xcrrugbsn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:focus-camera-auto" {...props}></Icon>
