<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj5kz30al.css';
import '../../css/n/nj0ynib6i.css';
import '../../css/r/r_993qgax.css';
import '../../css/u/ume3owb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bj5kz30al"/><path class="nj0ynib6i"/><path class="r_993qgax"/><path class="ume3owb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:dart" {...props}></Icon>
