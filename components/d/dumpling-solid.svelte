<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezqe3vhgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezqe3vhgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dumpling-solid" {...props}></Icon>
