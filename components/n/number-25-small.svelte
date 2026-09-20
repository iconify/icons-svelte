<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkanf8r8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkanf8r8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-25-small" {...props}></Icon>
