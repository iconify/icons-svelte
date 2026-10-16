<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb0q-t_1r.css';
import '../../css/g/g8k86tb-n.css';
import '../../css/k/k-qil1rqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gb0q-t_1r"/><path class="g8k86tb-n"/><path class="k-qil1rqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-balancing-20-bold" {...props}></Icon>
