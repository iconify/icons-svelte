<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj4cqpcwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj4cqpcwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:input-spark" {...props}></Icon>
