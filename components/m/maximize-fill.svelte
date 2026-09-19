<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo_o_wwux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo_o_wwux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:maximize-fill" {...props}></Icon>
