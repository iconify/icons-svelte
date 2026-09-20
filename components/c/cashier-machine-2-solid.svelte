<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z91v7ebgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z91v7ebgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cashier-machine-2-solid" {...props}></Icon>
