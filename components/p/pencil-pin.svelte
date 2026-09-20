<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekj4x8z7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekj4x8z7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-pin" {...props}></Icon>
