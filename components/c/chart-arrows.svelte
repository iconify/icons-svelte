<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfpq3ebrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfpq3ebrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-arrows" {...props}></Icon>
