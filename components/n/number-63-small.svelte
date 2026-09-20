<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka1pqbc-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka1pqbc-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-63-small" {...props}></Icon>
