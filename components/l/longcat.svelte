<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/g/gpzc3kb_a.css';
import '../../css/x/x-l1-u4wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1mjunbsu"><path clip-rule="evenodd" class="gpzc3kb_a"/><path class="x-l1-u4wm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:longcat" {...props}></Icon>
