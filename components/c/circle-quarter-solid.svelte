<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un8nmixra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un8nmixra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-quarter-solid" {...props}></Icon>
