<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_tcg2fse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_tcg2fse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:align-justify" {...props}></Icon>
