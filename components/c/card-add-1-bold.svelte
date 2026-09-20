<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qew2lt_vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qew2lt_vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:card-add-1-bold" {...props}></Icon>
