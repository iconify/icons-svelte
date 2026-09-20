<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9140c1rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9140c1rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cube-plus" {...props}></Icon>
