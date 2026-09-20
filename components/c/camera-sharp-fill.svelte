<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uon1petdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uon1petdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:camera-sharp-fill" {...props}></Icon>
