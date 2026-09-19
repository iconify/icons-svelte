<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/v/vdkj3yk3r.css';
import '../../css/b/bq9iuqbqy.css';
import '../../css/o/oh8-yacve.css';
import '../../css/n/n8o_jib3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path class="vdkj3yk3r"/><circle class="bq9iuqbqy"/><path class="oh8-yacve"/><path class="n8o_jib3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:flip-camera" {...props}></Icon>
