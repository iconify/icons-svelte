<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-2_bsb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-2_bsb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:curve" {...props}></Icon>
