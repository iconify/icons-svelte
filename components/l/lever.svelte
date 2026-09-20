<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9t7j4b3h.css';
import '../../css/a/amr0dcbch.css';
import '../../css/a/az17gfbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9t7j4b3h"/><path class="amr0dcbch"/><path class="az17gfbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lever" {...props}></Icon>
