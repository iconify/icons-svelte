<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spref0m5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spref0m5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:align-letter-right" {...props}></Icon>
