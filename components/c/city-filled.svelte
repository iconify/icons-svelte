<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abq6kacog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abq6kacog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:city-filled" {...props}></Icon>
