<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vuz12tb0u.css';
import '../../css/a/admehqbfz.css';
import '../../css/n/ntmphvbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vuz12tb0u"/><path class="admehqbfz"/><path class="ntmphvbwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:certificate" {...props}></Icon>
