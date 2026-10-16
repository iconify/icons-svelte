<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfo80ubkp.css';
import '../../css/j/jx6xceb7r.css';
import '../../css/b/b_flqm05r.css';
import '../../css/h/ho9tv7fwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfo80ubkp"/><path class="jx6xceb7r"/><path class="b_flqm05r"/><path class="ho9tv7fwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:photodiode-20-bold" {...props}></Icon>
