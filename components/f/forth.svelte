<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evjmnccgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":67.733,"height":67.733};
const content = `<path class="evjmnccgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:forth" {...props}></Icon>
