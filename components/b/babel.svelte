<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kev98l2gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kev98l2gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:babel" {...props}></Icon>
