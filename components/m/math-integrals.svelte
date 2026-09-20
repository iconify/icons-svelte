<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azhpgt8pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azhpgt8pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-integrals" {...props}></Icon>
