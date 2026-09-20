<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrw7cvbwr.css';
import '../../css/k/kqpp9twbz.css';
import '../../css/u/up9gopgdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrw7cvbwr"/><path class="kqpp9twbz"/><path class="up9gopgdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:capacitor-runtime-dark" {...props}></Icon>
