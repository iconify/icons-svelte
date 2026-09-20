<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pdj3gvbnp.css';
import '../../css/m/mys4ucbkk.css';
import '../../css/a/ajmr8884e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pdj3gvbnp"/><path class="mys4ucbkk"/><path class="ajmr8884e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:network-connector" {...props}></Icon>
