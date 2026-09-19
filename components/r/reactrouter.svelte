<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dghn0kt5a.css';
import '../../css/i/ioxby4bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dghn0kt5a"/><path class="ioxby4bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:reactrouter" {...props}></Icon>
