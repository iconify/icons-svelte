<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8mtjico.css';
import '../../css/l/l62m84s6k.css';
import '../../css/y/y-2ykkrlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pa8mtjico"/><path class="l62m84s6k"/><path class="y-2ykkrlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:manganese-48" {...props}></Icon>
