<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7-q9qbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7-q9qbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mojeek" {...props}></Icon>
