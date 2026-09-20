<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izgpe9bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izgpe9bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:playlist2" {...props}></Icon>
