<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqfy24bla.css';
import '../../css/i/ijmbz5bch.css';
import '../../css/u/u1ktodbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aqfy24bla"/><path class="ijmbz5bch"/><path class="u1ktodbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:drag" {...props}></Icon>
