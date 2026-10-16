<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt8f-3eoh.css';
import '../../css/i/i0ed3gb6r.css';
import '../../css/i/ilel_r_ca.css';
import '../../css/s/stu8q3lpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dt8f-3eoh"/><path class="i0ed3gb6r"/><path class="ilel_r_ca"/><path class="stu8q3lpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-sync-20-bold" {...props}></Icon>
