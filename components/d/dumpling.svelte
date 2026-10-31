<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpe4y4bdd.css';
import '../../css/a/a0m2q3bsg.css';
import '../../css/f/fqhq6fbgo.css';
import '../../css/e/edfqzq-tl.css';
import '../../css/s/ss0x5acba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="mpe4y4bdd"/><path class="a0m2q3bsg"/><path class="fqhq6fbgo"/><path class="edfqzq-tl"/><path class="ss0x5acba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:dumpling" {...props}></Icon>
