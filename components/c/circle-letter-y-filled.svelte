<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3fi0wiju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3fi0wiju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-y-filled" {...props}></Icon>
