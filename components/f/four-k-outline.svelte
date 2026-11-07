<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_as461dm.css';
import '../../css/m/mi_d81xnw.css';
import '../../css/k/k_haes9zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_as461dm"/><path class="mi_d81xnw"/><path clip-rule="evenodd" class="k_haes9zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:four-k-outline" {...props}></Icon>
