<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jq4kfps6d.css';
import '../../css/w/wacxq1bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="jq4kfps6d"/><path class="ouiIcon__fillSecondary wacxq1bmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-timelion" {...props}></Icon>
