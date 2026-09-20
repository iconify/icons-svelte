<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ary7gubza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ary7gubza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:noise-reduction" {...props}></Icon>
