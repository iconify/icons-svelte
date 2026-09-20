<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a97c0-fkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a97c0-fkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:home-filled" {...props}></Icon>
