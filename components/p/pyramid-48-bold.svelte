<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvfqi0v0k.css';
import '../../css/l/los2jo2ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lvfqi0v0k"/><path class="los2jo2ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pyramid-48-bold" {...props}></Icon>
