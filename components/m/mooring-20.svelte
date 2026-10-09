<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcd41kb4g.css';
import '../../css/n/n7msz9oby.css';
import '../../css/a/axlgonxbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mcd41kb4g"/><path class="n7msz9oby"/><path class="axlgonxbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mooring-20" {...props}></Icon>
