<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwzcd-pjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwzcd-pjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-u" {...props}></Icon>
