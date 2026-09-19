<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqlcj6blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqlcj6blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:airport-02" {...props}></Icon>
