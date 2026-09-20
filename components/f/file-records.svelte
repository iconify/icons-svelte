<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/ugqqb6qaw.css';
import '../../css/s/sk3mmrbov.css';
import '../../css/f/f9g5yw0qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugqqb6qaw"/><path class="sk3mmrbov"/><path class="f9g5yw0qa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-records" {...props}></Icon>
