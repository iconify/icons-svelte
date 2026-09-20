<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9hxg7tyk.css';
import '../../css/j/j6cvtntwi.css';
import '../../css/d/d4jypxbqx.css';
import '../../css/a/a7yq0nb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a9hxg7tyk"/><path class="j6cvtntwi"/><path class="d4jypxbqx"/><path class="a7yq0nb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:postcss" {...props}></Icon>
