<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h-1pmndiw.css';
import '../../css/k/k5j47ybbj.css';
import '../../css/f/fxa1sgb9k.css';
import '../../css/y/yzglel7sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h-1pmndiw"/><path class="k5j47ybbj"/><path class="fxa1sgb9k"/><path class="yzglel7sy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:rosette" {...props}></Icon>
