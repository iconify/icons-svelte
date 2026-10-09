<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0dvj9g4i.css';
import '../../css/i/iv3xvpmgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z0dvj9g4i"/><path class="iv3xvpmgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parking-48" {...props}></Icon>
