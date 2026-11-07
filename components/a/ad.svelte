<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajg2r_b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajg2r_b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:ad" {...props}></Icon>
