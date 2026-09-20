<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v18drh_jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v18drh_jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-outline" {...props}></Icon>
