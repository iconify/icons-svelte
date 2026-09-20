<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku6_nns4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku6_nns4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-vertically" {...props}></Icon>
