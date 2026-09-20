<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd720b16h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd720b16h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:arkecosystem" {...props}></Icon>
