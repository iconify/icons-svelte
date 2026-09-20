<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk9v8kbfn.css';
import '../../css/v/v2szjrygp.css';
import '../../css/t/tzko94lia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="uk9v8kbfn"/><path class="v2szjrygp"/><path class="tzko94lia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dvd" {...props}></Icon>
