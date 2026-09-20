<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdagz9b_g.css';
import '../../css/m/mf2faab1e.css';
import '../../css/p/p83k8_fbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdagz9b_g"/><path class="mf2faab1e"/><path class="p83k8_fbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:direction-dot-line" {...props}></Icon>
