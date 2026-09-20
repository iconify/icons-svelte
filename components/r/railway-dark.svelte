<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/j/jiz_soink.css';
import '../../css/i/iikk0lbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g class="n1mjunbsu"><path class="jiz_soink"/><path class="iikk0lbuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:railway-dark" {...props}></Icon>
