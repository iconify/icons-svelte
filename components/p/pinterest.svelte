<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld_gmp6sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld_gmp6sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pinterest" {...props}></Icon>
