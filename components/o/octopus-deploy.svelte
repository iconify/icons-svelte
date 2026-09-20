<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uflmedc9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uflmedc9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:octopus-deploy" {...props}></Icon>
