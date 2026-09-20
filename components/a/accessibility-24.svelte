<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twg_8sizo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twg_8sizo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:accessibility-24" {...props}></Icon>
