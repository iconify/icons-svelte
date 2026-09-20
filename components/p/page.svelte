<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_3-kybfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_3-kybfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:page" {...props}></Icon>
