<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyhh4ob9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyhh4ob9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:inner-shadow-top-filled" {...props}></Icon>
