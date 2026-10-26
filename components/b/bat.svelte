<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1uosnhiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z1uosnhiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:bat" {...props}></Icon>
