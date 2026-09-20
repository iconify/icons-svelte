<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb9fzlbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb9fzlbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-l" {...props}></Icon>
