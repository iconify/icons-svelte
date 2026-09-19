<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e7uv99btm.css';
import '../../css/q/qjd0nrblb.css';
import '../../css/v/vyste6pai.css';
import '../../css/w/w3p7knb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e7uv99btm"/><path class="qjd0nrblb"/><path class="vyste6pai"/><path class="w3p7knb-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:briefcase" {...props}></Icon>
