<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk7s-5bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wk7s-5bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-checks-duotone" {...props}></Icon>
