<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccsyvk3j.css';
import '../../css/o/otxs-bbsk.css';
import '../../css/k/kbn91fbuc.css';
import '../../css/y/ymlf35b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="otxs-bbsk"/><path class="kbn91fbuc"/><path class="ymlf35b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:prescription-20-bold" {...props}></Icon>
