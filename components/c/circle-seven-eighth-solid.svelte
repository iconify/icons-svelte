<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye0v996en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye0v996en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-seven-eighth-solid" {...props}></Icon>
