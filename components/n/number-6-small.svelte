<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea7lc5b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea7lc5b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-6-small" {...props}></Icon>
