<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubg3ixvlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubg3ixvlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:phone-missed-solid" {...props}></Icon>
