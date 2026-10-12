<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6p9yrlgi.css';
import '../../css/q/qhp5hjzez.css';
import '../../css/j/jt8rybcvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h6p9yrlgi"/><path class="qhp5hjzez"/><path class="jt8rybcvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chain-20" {...props}></Icon>
