<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z9vq6pbbz.css';
import '../../css/m/md286fbip.css';
import '../../css/x/xu6usccqt.css';
import '../../css/b/b5lcdgb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="z9vq6pbbz"/><g class="md286fbip"><path class="xu6usccqt"/><path class="b5lcdgb3h"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:block" {...props}></Icon>
