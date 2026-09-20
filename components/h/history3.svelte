<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdeg-9-5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdeg-9-5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:history3" {...props}></Icon>
