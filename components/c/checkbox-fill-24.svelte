<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kogph_qlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kogph_qlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:checkbox-fill-24" {...props}></Icon>
