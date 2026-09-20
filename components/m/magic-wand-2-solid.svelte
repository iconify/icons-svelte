<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehlrt2nct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehlrt2nct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:magic-wand-2-solid" {...props}></Icon>
