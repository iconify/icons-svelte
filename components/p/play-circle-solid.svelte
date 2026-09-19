<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp0wu5zpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp0wu5zpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:play-circle-solid" {...props}></Icon>
