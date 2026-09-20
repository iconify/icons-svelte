<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj5i637zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj5i637zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-circle-fill" {...props}></Icon>
