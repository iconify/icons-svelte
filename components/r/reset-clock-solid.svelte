<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shdj2qbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shdj2qbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:reset-clock-solid" {...props}></Icon>
