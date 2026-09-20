<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byz9vkb6r.css';
import '../../css/k/ksdy6lv1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="byz9vkb6r"/><path class="ksdy6lv1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:lock-open-outline" {...props}></Icon>
