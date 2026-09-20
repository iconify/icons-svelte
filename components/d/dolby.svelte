<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vet4z41ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vet4z41ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dolby" {...props}></Icon>
