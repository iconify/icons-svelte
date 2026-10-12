<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1dk65itc.css';
import '../../css/r/roxo87l1y.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o1dk65itc"/><path class="roxo87l1y"/><path class="hwjgqrbah"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-x-48-bold" {...props}></Icon>
