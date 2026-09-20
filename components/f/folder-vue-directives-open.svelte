<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1hbf2blw.css';
import '../../css/y/y_4y_gbst.css';
import '../../css/d/dwj5ymbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p1hbf2blw"/><path class="y_4y_gbst"/><path class="dwj5ymbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-vue-directives-open" {...props}></Icon>
