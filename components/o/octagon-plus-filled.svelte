<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-eljtb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-eljtb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-plus-filled" {...props}></Icon>
