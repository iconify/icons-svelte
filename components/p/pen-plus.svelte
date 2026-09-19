<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt1e66bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt1e66bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-plus" {...props}></Icon>
