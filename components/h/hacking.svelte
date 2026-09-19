<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/f/f2wcktryo.css';
import '../../css/f/f_056cc9h.css';
import '../../css/i/i-qglfbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="f2wcktryo"/><path class="f_056cc9h"/></g><path class="i-qglfbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:hacking" {...props}></Icon>
