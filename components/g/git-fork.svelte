<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/b/bn5ilqppl.css';
import '../../css/p/ppzqy-bxa.css';
import '../../css/o/ouxzqo9mb.css';
import '../../css/d/dfqro5y3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="bn5ilqppl"/><circle class="ppzqy-bxa"/><circle class="ouxzqo9mb"/><path class="dfqro5y3h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:git-fork" {...props}></Icon>
