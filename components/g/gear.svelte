<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l-1rtqbij.css';
import '../../css/w/wkithdmnp.css';
import '../../css/m/myal57b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l-1rtqbij"/><path class="wkithdmnp"/><path class="myal57b7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:gear" {...props}></Icon>
