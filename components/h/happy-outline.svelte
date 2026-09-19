<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wemwzxbiv.css';
import '../../css/b/bqauwdvox.css';
import '../../css/c/cu_iqhliu.css';
import '../../css/w/w84vznkgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wemwzxbiv"/><path class="bqauwdvox"/><circle class="cu_iqhliu"/><circle class="w84vznkgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:happy-outline" {...props}></Icon>
