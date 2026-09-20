<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euc_4hbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="euc_4hbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:drone-solid" {...props}></Icon>
