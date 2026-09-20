<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phqysqbjw.css';
import '../../css/d/dinarbh3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="phqysqbjw"/><path class="dinarbh3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:handlebars" {...props}></Icon>
