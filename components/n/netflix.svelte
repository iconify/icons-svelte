<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py--2fjvj.css';
import '../../css/n/nthaozbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":24};
const content = `<path class="py--2fjvj"/><path class="nthaozbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:netflix" {...props}></Icon>
