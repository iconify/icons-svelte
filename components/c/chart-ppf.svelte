<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ade1qzjom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ade1qzjom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-ppf" {...props}></Icon>
