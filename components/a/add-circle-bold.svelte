<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un4-q6b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un4-q6b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:add-circle-bold" {...props}></Icon>
