<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8syq0b9t.css';
import '../../css/u/uk19ffbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s8syq0b9t"/><path class="uk19ffbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rain-gauge-48-bold" {...props}></Icon>
