<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahadrc3vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahadrc3vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:directions-fill" {...props}></Icon>
