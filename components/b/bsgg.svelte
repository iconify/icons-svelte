<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5_mrgt4f.css';
import '../../css/f/f86ggwbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5_mrgt4f"/><path class="f86ggwbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bsgg" {...props}></Icon>
