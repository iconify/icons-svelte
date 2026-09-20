<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2zpr77lu.css';
import '../../css/q/qhpij3bsp.css';
import '../../css/o/ofnfaeuml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="b2zpr77lu"><path class="qhpij3bsp"/><path class="ofnfaeuml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:posthtml" {...props}></Icon>
