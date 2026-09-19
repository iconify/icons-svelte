<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/ypjg7bbdz.css';
import '../../css/n/n50kjvxhj.css';
import '../../css/d/d7mhh30wi.css';
import '../../css/k/kt5shjbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ypjg7bbdz"/><rect class="n50kjvxhj"/><path class="d7mhh30wi"/><path class="kt5shjbak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:juice" {...props}></Icon>
