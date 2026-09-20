<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njun85gyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="njun85gyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:double-heart-solid" {...props}></Icon>
