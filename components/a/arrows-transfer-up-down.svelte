<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t67i64bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t67i64bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-transfer-up-down" {...props}></Icon>
