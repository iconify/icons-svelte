<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt04zybco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt04zybco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery" {...props}></Icon>
