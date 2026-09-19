<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fe6_45bhk.css';
import '../../css/w/wx1w62bye.css';
import '../../css/c/ca1uvsbeh.css';
import '../../css/e/eh5-hca6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fe6_45bhk"/><path class="wx1w62bye"/><path class="ca1uvsbeh"/><path class="eh5-hca6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:leaf-fluttering-in-wind" {...props}></Icon>
